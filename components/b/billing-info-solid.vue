<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcsyndb6q.css';
import '../../css/k/kzh5-ccpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcsyndb6q"/><path class="kzh5-ccpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:billing-info-solid" /></template>
