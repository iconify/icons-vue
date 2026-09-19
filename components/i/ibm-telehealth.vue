<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkg334b8z.css';
import '../../css/r/r3uwgacnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gkg334b8z"/><path class="r3uwgacnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-telehealth" /></template>
