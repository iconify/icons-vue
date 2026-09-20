<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbv6d6uqd.css';
import '../../css/u/u27wnzbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbv6d6uqd"/><path class="u27wnzbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:hi-hat-24" /></template>
