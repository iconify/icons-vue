<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tytuppbws.css';
import '../../css/e/edp-a4blw.css';
import '../../css/z/z87r79bhv.css';
import '../../css/q/q01mz1cnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tytuppbws"/><path class="edp-a4blw"/><path class="z87r79bhv"/><path class="q01mz1cnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:email-filled" /></template>
