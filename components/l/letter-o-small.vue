<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nas-ckb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nas-ckb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-o-small" /></template>
