<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhlkhxbii.css';
import '../../css/b/bp4av50wq.css';
import '../../css/s/soawemmgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhlkhxbii"/><path class="bp4av50wq"/><path class="soawemmgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-swisstransfer-dark" /></template>
