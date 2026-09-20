<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv8-yz4el.css';
import '../../css/k/k6cmp2alc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8-yz4el"/><path clip-rule="evenodd" class="k6cmp2alc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-triangle" /></template>
