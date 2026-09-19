<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk_glsbdf.css';
import '../../css/r/r3m6txini.css';
import '../../css/z/z5lj_d9rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk_glsbdf"/><path class="r3m6txini"/><path class="z5lj_d9rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fridge" /></template>
