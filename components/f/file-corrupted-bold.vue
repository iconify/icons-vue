<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhj7tk-5q.css';
import '../../css/c/cvj_c0b3m.css';
import '../../css/n/nqjdsphxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path class="cvj_c0b3m"/><path class="nqjdsphxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-corrupted-bold" /></template>
