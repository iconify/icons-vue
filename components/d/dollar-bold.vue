<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlc6xfqvl.css';
import '../../css/q/qqluwf17f.css';
import '../../css/r/rwbdnz60g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlc6xfqvl"/><path class="qqluwf17f"/><path clip-rule="evenodd" class="rwbdnz60g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dollar-bold" /></template>
