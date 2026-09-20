<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6yqbbtn.css';
import '../../css/c/ceo0jccjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6yqbbtn"/><path class="ceo0jccjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:grape-filled" /></template>
