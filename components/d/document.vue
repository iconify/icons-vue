<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-fhbk.css';
import '../../css/q/qa-o7h.css';
import '../../css/a/ab0nvj.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-fhbk qa-o7h"/><path class="ab0nvj qa-o7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:document" /></template>
