<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrnj_zb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrnj_zb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:copy-x-filled" /></template>
