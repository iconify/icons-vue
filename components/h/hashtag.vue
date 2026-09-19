<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq_y27ygp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq_y27ygp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:hashtag" /></template>
