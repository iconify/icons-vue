<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lurbt5era.css';
import '../../css/l/layi-mb4r.css';
import '../../css/k/ks9c86i1m.css';
import '../../css/c/cwafcrynf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":320};
const content = `<path class="lurbt5era"/><path class="layi-mb4r"/><path class="ks9c86i1m"/><path class="cwafcrynf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lit" /></template>
