<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9cib2wjc.css';
import '../../css/r/reay3euxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z9cib2wjc"/><path class="reay3euxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:investment" /></template>
