<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8uix_bml.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cjqtp0b_c.css';
import '../../css/g/g2ncgwkcx.css';
import '../../css/e/esaau7bpo.css';
import '../../css/k/kz79jgp0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8uix_bml secondary"/><g class="dt0cm9dhy primary"><path class="cjqtp0b_c"/><path class="g2ncgwkcx"/><path class="esaau7bpo"/><path class="kz79jgp0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-input-duo" /></template>
