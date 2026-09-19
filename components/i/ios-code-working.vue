<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funu2bcxe.css';
import '../../css/r/r7co23qft.css';
import '../../css/f/fn167tpom.css';
import '../../css/v/vzs57rbrx.css';
import '../../css/s/sch1b7e_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="funu2bcxe"/><path class="r7co23qft"/><circle class="fn167tpom"/><circle class="vzs57rbrx"/><circle class="sch1b7e_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-code-working" /></template>
