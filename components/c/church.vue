<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnrx27ndk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qnrx27ndk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:church" /></template>
