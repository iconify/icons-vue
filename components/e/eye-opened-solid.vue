<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6uz3dquh.css';
import '../../css/c/cn5tumcdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6uz3dquh"/><path class="cn5tumcdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:eye-opened-solid" /></template>
