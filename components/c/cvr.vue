<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-jhyvbes.css';
import '../../css/b/bk7etbbhv.css';
import '../../css/z/zxjlc_52g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-jhyvbes"/><path class="bk7etbbhv"/><path class="zxjlc_52g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cvr" /></template>
