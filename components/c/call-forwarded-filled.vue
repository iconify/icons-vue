<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7q3yfbdi.css';
import '../../css/p/p9omok_2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7q3yfbdi"/><path class="p9omok_2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:call-forwarded-filled" /></template>
