<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uws2288gp.css';
import '../../css/b/b9dmkccal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uws2288gp"/><path class="b9dmkccal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:eye-opened" /></template>
