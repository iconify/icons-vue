<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms2gyg5jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms2gyg5jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anydesk" /></template>
