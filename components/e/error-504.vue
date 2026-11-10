<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6o6lgbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6o6lgbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:error-504" /></template>
