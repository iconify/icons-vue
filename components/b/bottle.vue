<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls08edcnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="ls08edcnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bottle" /></template>
