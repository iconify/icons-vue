<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb717xbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb717xbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dots-diagonal-2" /></template>
