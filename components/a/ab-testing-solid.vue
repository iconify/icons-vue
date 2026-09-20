<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luxx0zeko.css';
import '../../css/o/oc-e4mb7v.css';
import '../../css/i/i8e6vr1if.css';
import '../../css/w/wut-a81uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="luxx0zeko"/><path clip-rule="evenodd" class="oc-e4mb7v"/><path class="i8e6vr1if"/><path clip-rule="evenodd" class="wut-a81uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ab-testing-solid" /></template>
