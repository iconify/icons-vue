<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcay3j-in.css';
import '../../css/s/seqwdcaye.css';
import '../../css/j/jmfazjblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcay3j-in"/><path class="seqwdcaye"/><path class="jmfazjblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:compass" /></template>
