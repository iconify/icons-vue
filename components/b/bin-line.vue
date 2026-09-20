<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl2ciyngq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl2ciyngq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bin-line" /></template>
