<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkw_-pbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkw_-pbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brightness-filled" /></template>
