<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs_4bcclq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs_4bcclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-waves-solid" /></template>
