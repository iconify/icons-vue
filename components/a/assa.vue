<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opi4shb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opi4shb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:assa" /></template>
