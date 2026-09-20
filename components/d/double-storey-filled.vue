<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdtr-tgcy.css';
import '../../css/x/xqehzub3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtr-tgcy"/><path class="xqehzub3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:double-storey-filled" /></template>
