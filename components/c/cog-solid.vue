<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7wg9bkj.css';
import '../../css/e/enbl2qcxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hu7wg9bkj"/><path clip-rule="evenodd" class="enbl2qcxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cog-solid" /></template>
