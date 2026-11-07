<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii24kzbxm.css';
import '../../css/x/xejlx-96v.css';
import '../../css/z/zly6tablv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii24kzbxm"/><path class="xejlx-96v"/><path clip-rule="evenodd" class="zly6tablv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightning-outline" /></template>
