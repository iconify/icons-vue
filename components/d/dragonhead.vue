<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1cffchus.css';
import '../../css/v/v5048sbmk.css';
import '../../css/n/n924abcqn.css';
import '../../css/a/aht29abkg.css';
import '../../css/n/ne73a8bqm.css';
import '../../css/b/bevi74bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e1cffchus"/><path class="v5048sbmk"/><path class="n924abcqn"/><path class="aht29abkg"/><path class="ne73a8bqm"/><path class="bevi74bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dragonhead" /></template>
