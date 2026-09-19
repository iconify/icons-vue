<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc7fzmsbi.css';
import '../../css/t/t4p58ib0k.css';
import '../../css/g/gv02961wk.css';
import '../../css/a/acfq-db-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sc7fzmsbi"/><path class="t4p58ib0k"/><path class="gv02961wk"/><path class="acfq-db-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-crop" /></template>
