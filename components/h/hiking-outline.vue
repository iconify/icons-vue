<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cur_krbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cur_krbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-outline" /></template>
