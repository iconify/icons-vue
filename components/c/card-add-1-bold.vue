<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qew2lt_vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qew2lt_vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:card-add-1-bold" /></template>
