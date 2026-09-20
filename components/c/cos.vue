<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cibmyoejo.css';
import '../../css/t/tj7kutb3g.css';
import '../../css/t/t0c6ekb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cibmyoejo"/><path class="tj7kutb3g"/><path class="t0c6ekb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cos" /></template>
