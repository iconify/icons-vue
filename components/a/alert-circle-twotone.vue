<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/y/ysxzor.css';
import '../../css/s/sqpi1o.css';
import '../../css/y/y4wbml.css';
import '../../css/n/neinwl.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew ysxzor"/><path class="iw1iew sqpi1o y4wbml"/><path class="iw1iew neinwl y4wbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:alert-circle-twotone" /></template>
