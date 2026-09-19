<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbpfbqfii.css';
import '../../css/n/nrolmxo4x.css';
import '../../css/j/jophfjbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="mbpfbqfii"/><path class="nrolmxo4x"/><path class="jophfjbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:doctor" /></template>
