<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugy8c7c-s.css';
import '../../css/h/hanozbgcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugy8c7c-s"/><path class="hanozbgcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:csv-file" /></template>
