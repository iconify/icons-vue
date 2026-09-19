<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvuvw1xmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvuvw1xmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:clipboard-outline" /></template>
