<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnsslsbew.css';
import '../../css/b/bog13w73d.css';
import '../../css/k/kila4w3tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsslsbew"/><path class="bog13w73d"/><path class="kila4w3tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:billing-info-duotone" /></template>
