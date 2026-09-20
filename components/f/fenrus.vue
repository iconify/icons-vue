<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uslf4acad.css';
import '../../css/i/ia682rbyt.css';
import '../../css/r/r6heypbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uslf4acad"/><path class="ia682rbyt"/><path class="r6heypbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fenrus" /></template>
