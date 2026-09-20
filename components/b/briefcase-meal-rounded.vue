<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf6vhbcfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:briefcase-meal-rounded" /></template>
<style>
.pf6vhbcfc {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7H9V5.615q0-.69.463-1.153T10.616 4h2.769q.69 0 1.153.462T15 5.615V7h4.385q.69 0 1.152.463T21 8.616v9.769q0 .69-.463 1.153T19.385 20zM10 7h4V5.615q0-.23-.192-.423T13.385 5h-2.77q-.23 0-.423.192T10 5.615zm-.442 12v-3.596q.496-.131.834-.553q.339-.422.339-.968v-2.787q0-.161-.121-.282q-.121-.122-.283-.122t-.273.122t-.112.282v2.564h-.596v-2.564q0-.161-.111-.282q-.112-.122-.273-.122t-.273.122t-.112.282v2.564h-.596v-2.564q0-.161-.112-.282q-.111-.122-.273-.122t-.273.122t-.112.282v2.787q0 .546.33.968q.328.422.843.553V19zm6.058 0v-2.97q.496-.291.834-.987t.339-1.6q0-1.143-.519-1.947q-.518-.804-1.231-.804q-.739 0-1.254.804q-.516.804-.516 1.946q0 .9.329 1.595q.329.696.844.994V19z");
}

</style>
