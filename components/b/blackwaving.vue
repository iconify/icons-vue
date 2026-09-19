<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ichh20b6b.css';
import '../../css/f/f4xgot2-t.css';
import '../../css/s/sshvt2bwd.css';
import '../../css/d/dmmpmib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ichh20b6b"/><path class="f4xgot2-t"/><path class="sshvt2bwd"/><path class="dmmpmib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blackwaving" /></template>
