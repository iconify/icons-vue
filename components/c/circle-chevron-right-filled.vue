<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf_-qtb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf_-qtb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-chevron-right-filled" /></template>
