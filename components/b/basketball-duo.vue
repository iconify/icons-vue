<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogahin_3h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z5s_iw4ay.css';
import '../../css/e/e33_rkbbn.css';
import '../../css/a/afv3k-bvd.css';
import '../../css/t/td5s74bhk.css';
import '../../css/g/glvsztbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogahin_3h secondary"/><g class="dt0cm9dhy primary"><path class="z5s_iw4ay"/><path class="e33_rkbbn"/><path class="afv3k-bvd"/><path class="td5s74bhk"/><path class="glvsztbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:basketball-duo" /></template>
