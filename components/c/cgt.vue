<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5l1xgljl.css';
import '../../css/e/ec-xsg-ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5l1xgljl"/><path class="ec-xsg-ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cgt" /></template>
