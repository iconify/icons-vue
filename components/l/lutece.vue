<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8a58u7ck.css';
import '../../css/l/lw9qbabax.css';
import '../../css/f/fq7kcxiwl.css';
import '../../css/g/gqlpjnibd.css';
import '../../css/x/xppy41w3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100,"top":-33.5};
const content = `<path class="s8a58u7ck"/><path class="lw9qbabax"/><path class="fq7kcxiwl"/><path class="gqlpjnibd"/><path class="xppy41w3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lutece" /></template>
