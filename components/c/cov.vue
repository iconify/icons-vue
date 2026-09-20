<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viskcjbkm.css';
import '../../css/f/f8s_4jbup.css';
import '../../css/o/o8qnxtb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="viskcjbkm"/><path class="f8s_4jbup"/><path class="o8qnxtb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cov" /></template>
