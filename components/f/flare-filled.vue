<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdd2oyajs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdd2oyajs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flare-filled" /></template>
