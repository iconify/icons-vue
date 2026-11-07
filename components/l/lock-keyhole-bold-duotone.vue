<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dnrk_0v.css';
import '../../css/r/r3h-ltb-k.css';
import '../../css/t/t2or4horf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="r3h-ltb-k"/><path class="t2or4horf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-bold-duotone" /></template>
