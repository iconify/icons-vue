<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw0k5bban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0k5bban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:database-cog-solid" /></template>
