<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofqcakjlm.css';
import '../../css/l/lr1fnhkrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofqcakjlm"/><path class="lr1fnhkrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:billing-info" /></template>
