<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-trjsbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-rounded" /></template>
<style>
.k-trjsbqs {
  fill: currentColor;
  d: path("M7.549 16.548q.22-.222.22-.55t-.221-.547t-.55-.22t-.547.221t-.22.55t.221.547t.55.22t.547-.221m-.906-8.904Q6.5 7.788 6.5 8v5.27q0 .212.144.356t.357.143t.356-.144t.143-.356V8q0-.213-.144-.356T6.999 7.5t-.356.144M17 16.5q.213 0 .356-.144t.144-.357t-.144-.356T17 15.5h-5q-.213 0-.356.144t-.144.357t.144.356t.356.143zm0-4q.213 0 .356-.144t.144-.357t-.144-.356T17 11.5h-5q-.213 0-.356.144t-.144.357t.144.356t.356.143zm0-4q.213 0 .356-.144t.144-.357t-.144-.356T17 7.5h-5q-.213 0-.356.144t-.144.357t.144.356T12 8.5zM4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20z");
}

</style>
