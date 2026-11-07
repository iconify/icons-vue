<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zenyhg4uf.css';
import '../../css/u/u6-32zbnu.css';
import '../../css/f/fpad1pbpd.css';
import '../../css/k/kh1beibzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zenyhg4uf"/><path class="u6-32zbnu"/><path class="fpad1pbpd"/><path class="kh1beibzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:colour-tuning-bold-duotone" /></template>
