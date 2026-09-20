<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjk7blide.css';
import '../../css/t/tfmdi36dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjk7blide"/><path class="tfmdi36dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:exit" /></template>
