<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs_t-dgjs.css';
import '../../css/b/b_zpflbco.css';
import '../../css/g/gt8ehhy9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fs_t-dgjs"/><path class="b_zpflbco"/><path class="gt8ehhy9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-keyboard-button" /></template>
