<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdw6n2bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="mdw6n2bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:image" /></template>
