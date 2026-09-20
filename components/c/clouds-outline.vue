<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heqy_fk9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="heqy_fk9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clouds-outline" /></template>
