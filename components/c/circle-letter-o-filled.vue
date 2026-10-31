<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn62sxfmg.css';
import '../../css/q/ql32cplmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn62sxfmg"/><path clip-rule="evenodd" class="ql32cplmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-o-filled" /></template>
