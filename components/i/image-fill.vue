<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smbn1vbdh.css';
import '../../css/g/ghwq-ivuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smbn1vbdh"/><path class="ghwq-ivuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:image-fill" /></template>
