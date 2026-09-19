<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afnpse13x.css';
import '../../css/n/n3zmfgmgx.css';
import '../../css/k/kcvmbebru.css';
import '../../css/l/l2igllydu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afnpse13x"/><ellipse class="n3zmfgmgx"/><path class="kcvmbebru"/><path class="l2igllydu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cookedrice" /></template>
