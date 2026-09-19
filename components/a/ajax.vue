<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnnnaqbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":767,"height":1024};
const content = `<path class="gnnnaqbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ajax" /></template>
