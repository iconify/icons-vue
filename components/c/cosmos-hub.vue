<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9p35ebyv.css';
import '../../css/t/tn1bqmqhf.css';
import '../../css/f/fle4ekbxc.css';
import '../../css/m/m2bcqj2zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9p35ebyv"/><path clip-rule="evenodd" class="tn1bqmqhf"/><path class="fle4ekbxc"/><path clip-rule="evenodd" class="m2bcqj2zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cosmos-hub" /></template>
