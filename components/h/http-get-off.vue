<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9dn8cb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9dn8cb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:http-get-off" /></template>
