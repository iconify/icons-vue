<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x47gr45iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x47gr45iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-caret-left-filled" /></template>
