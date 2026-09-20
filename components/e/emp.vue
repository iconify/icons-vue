<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lua9-g0jf.css';
import '../../css/d/dsjuhdb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lua9-g0jf"/><path class="dsjuhdb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:emp" /></template>
