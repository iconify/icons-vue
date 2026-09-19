<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szd676lcr.css';
import '../../css/m/mgm68nbdh.css';
import '../../css/t/tg78mwbgu.css';
import '../../css/j/j4bam6bye.css';
import '../../css/m/mw25ogbwg.css';
import '../../css/s/slx8bnllt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szd676lcr"/><path class="mgm68nbdh"/><path class="tg78mwbgu"/><path class="j4bam6bye"/><path class="mw25ogbwg"/><path class="slx8bnllt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-endpoints" /></template>
