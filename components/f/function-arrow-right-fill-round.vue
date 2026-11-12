<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyrhlk_1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:function-arrow-right-fill-round" /></template>
<style>
.eyrhlk_1u {
  fill: currentColor;
  d: path("M9.97 8.243L9.781 9H12a1 1 0 0 1 0 2H9.281L7.97 16.243q-.165.668-.339 1.334c-.232.874-.517 1.973-1.174 2.63c-.42.42-.986.637-1.566.72C4.267 21.017 3.629 21 3 21a1 1 0 0 1 0-2c.322 0 .644.001.965-.007c.255-.007.89-.012 1.078-.2c.176-.177.306-.565.383-.797q.175-.526.604-2.239L7.219 11H5a1 1 0 0 1 0-2h2.719l.311-1.243q.165-.668.339-1.334c.232-.874.517-1.973 1.174-2.63c.42-.42.986-.637 1.566-.72C11.733 2.983 12.371 3 13 3a1 1 0 0 1 0 2c-.322 0-.644-.001-.965.007c-.255.007-.89.012-1.078.2c-.176.177-.306.565-.383.797q-.175.525-.604 2.239m8.737 2.05l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L18.586 15H13a1 1 0 0 1 0-2h5.586l-1.293-1.293a1 1 0 0 1 1.414-1.414");
}

</style>
