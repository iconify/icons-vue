<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsx9eqb7z.css';
import '../../css/t/t0y9dydjl.css';
import '../../css/v/v96txsrdu.css';
import '../../css/d/d7-7yjbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dsx9eqb7z"/><path class="t0y9dydjl"/><path class="v96txsrdu"/><path class="d7-7yjbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-storage-20-bold" /></template>
