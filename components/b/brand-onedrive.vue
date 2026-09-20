<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjw8acbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjw8acbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-onedrive" /></template>
