<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn55krb2z.css';
import '../../css/r/r-xntnbat.css';
import '../../css/d/dfjq7mbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="jn55krb2z"/><rect class="r-xntnbat"/><path class="dfjq7mbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-vertical-justify-start-filled" /></template>
