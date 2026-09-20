<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_gtpf7cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="r_gtpf7cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:lifebuoy-f" /></template>
