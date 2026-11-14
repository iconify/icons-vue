<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfaohpg6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hair-wax-tin" /></template>
<style>
.nfaohpg6o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7.001v-.002q0-1.605 3.184-2.49q2.735-.76 6.566-.76t6.566.76q3.186.885 3.184 2.49q.001.901-1 1.575V16.5q0 3.5-8.75 3.5t-8.75-3.5V8.574q-1-.673-1-1.573m2.5 7.797V16.5q0 .604 1.837 1.235Q8.812 18.5 12 18.5t5.413-.765q1.837-.631 1.837-1.235v-1.702Q17.127 16 12 16t-7.25-1.202m14.5-2.298V9.28q-.321.11-.684.211q-2.735.76-6.566.76t-6.566-.76q-.363-.101-.684-.211v3.22q0 .604 1.837 1.235Q8.812 14.5 12 14.5t5.413-.765q1.837-.631 1.837-1.235");
}

</style>
