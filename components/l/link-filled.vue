<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2oc1ljfc.css';
import '../../css/o/olpmu-5dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2oc1ljfc"/><path class="olpmu-5dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:link-filled" /></template>
