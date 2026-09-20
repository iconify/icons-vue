<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grkthnbuz.css';
import '../../css/z/z46kzigug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grkthnbuz"/><path class="z46kzigug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jetblue-airways" /></template>
