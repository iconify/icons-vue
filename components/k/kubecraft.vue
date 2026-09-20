<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4imvxbfg.css';
import '../../css/p/pdqwe3x1i.css';
import '../../css/a/a2shhjbqb.css';
import '../../css/e/eldq07ydi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s4imvxbfg"/><path class="pdqwe3x1i"/><path class="a2shhjbqb"/><path class="eldq07ydi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubecraft" /></template>
