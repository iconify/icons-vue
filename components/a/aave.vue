<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz1zejb7f.css';
import '../../css/i/i9lomcmsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz1zejb7f"/><path class="i9lomcmsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aave" /></template>
