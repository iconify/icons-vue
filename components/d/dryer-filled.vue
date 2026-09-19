<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq3pidbpg.css';
import '../../css/l/l93btfbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq3pidbpg"/><path class="l93btfbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dryer-filled" /></template>
