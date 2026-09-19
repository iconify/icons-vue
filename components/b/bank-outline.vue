<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv6br_-mv.css';
import '../../css/c/ca-rzg1lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv6br_-mv"/><path class="ca-rzg1lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bank-outline" /></template>
