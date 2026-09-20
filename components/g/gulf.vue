<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1u_yzaak.css';
import '../../css/d/dagp_7b_p.css';
import '../../css/v/vl4thlbxt.css';
import '../../css/v/vb_zqjsyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1u_yzaak"/><path class="dagp_7b_p"/><path class="vl4thlbxt"/><path class="vb_zqjsyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gulf" /></template>
