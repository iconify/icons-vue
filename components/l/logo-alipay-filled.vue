<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sklr68b5u.css';
import '../../css/r/rkkr41y9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sklr68b5u"/><path class="rkkr41y9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-alipay-filled" /></template>
