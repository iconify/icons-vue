<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjokqrbgh.css';
import '../../css/s/swl_b_b0a.css';
import '../../css/i/i39yq9nqy.css';
import '../../css/n/ngl64r_9r.css';
import '../../css/k/krbgelbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="zjokqrbgh"/><path clip-rule="evenodd" class="swl_b_b0a"/><path clip-rule="evenodd" class="i39yq9nqy"/><path clip-rule="evenodd" class="ngl64r_9r"/><circle clip-rule="evenodd" class="krbgelbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:imac" /></template>
