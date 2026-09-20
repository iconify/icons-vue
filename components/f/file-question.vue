<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adm_kkbuq.css';
import '../../css/m/mus2fv8bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adm_kkbuq"/><path class="mus2fv8bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:file-question" /></template>
