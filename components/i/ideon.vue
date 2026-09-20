<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcx6q5b0x.css';
import '../../css/k/k5lp20bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcx6q5b0x"/><path class="k5lp20bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ideon" /></template>
