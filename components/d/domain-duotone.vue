<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zixyvouym.css';
import '../../css/k/kbc9ywbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zixyvouym"/><path class="kbc9ywbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:domain-duotone" /></template>
