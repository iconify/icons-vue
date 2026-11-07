<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3uje9bbo.css';
import '../../css/v/v1qydc12m.css';
import '../../css/e/er-a0qb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3uje9bbo"/><path class="v1qydc12m"/><path class="er-a0qb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-bold-duotone" /></template>
