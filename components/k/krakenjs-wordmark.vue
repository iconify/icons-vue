<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4e2dybch.css';
import '../../css/i/ibasdbcyq.css';
import '../../css/q/qiv3vz5la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="p4e2dybch"/><path class="ibasdbcyq"/><path class="qiv3vz5la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:krakenjs-wordmark" /></template>
