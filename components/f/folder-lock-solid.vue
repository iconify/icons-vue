<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1qmh6bea.css';
import '../../css/k/k52lm57aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1qmh6bea"/><path clip-rule="evenodd" class="k52lm57aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-lock-solid" /></template>
