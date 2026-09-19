<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qugridcza.css';
import '../../css/k/k2zwb4blz.css';
import '../../css/i/igcb-e3sx.css';
import '../../css/g/gk5cqqbli.css';
import '../../css/b/b-ui5dj6i.css';
import '../../css/n/nus6nu-8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qugridcza"/><path class="k2zwb4blz"/><path class="igcb-e3sx"/><path class="gk5cqqbli"/><path class="b-ui5dj6i"/><path class="nus6nu-8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:classicalbuilding" /></template>
