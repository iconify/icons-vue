<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at07s5byk.css';
import '../../css/n/n3ikn2b4s.css';
import '../../css/b/b_3oa7bkg.css';
import '../../css/d/d5y5ipbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="at07s5byk"/><circle class="n3ikn2b4s"/><path class="b_3oa7bkg"/><path class="d5y5ipbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:koreaflag" /></template>
