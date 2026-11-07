<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td855uyua.css';
import '../../css/x/x6t1awols.css';
import '../../css/d/d0nccrbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td855uyua"/><path class="x6t1awols"/><path clip-rule="evenodd" class="d0nccrbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-4-outline" /></template>
