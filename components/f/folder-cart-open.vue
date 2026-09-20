<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-qxuibhr.css';
import '../../css/n/ng2kf2fda.css';
import '../../css/i/i6utg9b0i.css';
import '../../css/c/c1ia1gbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-qxuibhr"/><circle class="ng2kf2fda"/><circle class="i6utg9b0i"/><path class="c1ia1gbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cart-open" /></template>
