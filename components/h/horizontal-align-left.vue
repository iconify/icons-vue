<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4z5ngy-x.css';
import '../../css/x/xqiru0m4e.css';
import '../../css/b/blbmi0irt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4z5ngy-x"/><path class="xqiru0m4e"/><path class="blbmi0irt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:horizontal-align-left" /></template>
