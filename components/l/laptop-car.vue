<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk7o6lbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-car" /></template>
<style>
.bk7o6lbvj {
  fill: currentColor;
  d: path("M2 19v-1.5h2V6.616q0-.667.475-1.141T5.615 5h11.77q.666 0 1.14.475T19 6.615v2.27h-6.958q-.905 0-1.645.487q-.74.488-1.033 1.34L7.846 15.05V19zm8.65 2q-.177 0-.298-.121q-.121-.12-.121-.298v-5.094l1.271-3.677q.087-.243.29-.392t.468-.149h6.711q.265 0 .468.15q.203.148.29.39L21 15.488v5.094q0 .177-.121.298q-.12.121-.298.121h-.162q-.177 0-.298-.121q-.121-.12-.121-.298V19.5h-8.77v1.08q0 .178-.12.299q-.121.121-.298.121zm.777-6.23h8.377l-.894-2.616h-6.59zm1.765 3.25q.376 0 .63-.26q.255-.258.255-.626q0-.367-.259-.625q-.258-.259-.626-.259t-.626.259t-.258.625t.254.626t.63.26m4.847 0q.376 0 .63-.26q.254-.258.254-.626q0-.367-.258-.625q-.26-.259-.626-.259t-.627.259q-.258.258-.258.625q0 .368.254.626q.254.26.63.26");
}

</style>
