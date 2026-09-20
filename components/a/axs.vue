<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lef6v5bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lef6v5bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:axs" /></template>
