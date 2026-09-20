<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy37zibmr.css';
import '../../css/o/o15ae4bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy37zibmr"/><path class="o15ae4bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:convoy" /></template>
