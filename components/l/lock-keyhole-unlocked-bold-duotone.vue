<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3dnrk_0v.css';
import '../../css/r/r3h-ltb-k.css';
import '../../css/s/sl_boeb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="r3h-ltb-k"/><path class="sl_boeb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-unlocked-bold-duotone" /></template>
