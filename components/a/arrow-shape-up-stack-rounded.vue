<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcge4oc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-stack-rounded" /></template>
<style>
.pcge4oc_h {
  fill: currentColor;
  d: path("M9.462 18.192V16.02H6.385q-.403 0-.565-.363q-.162-.364.127-.66l5.456-5.838q.237-.254.593-.254t.6.254l5.455 5.838q.289.296.127.66q-.162.363-.565.363h-3.075v2.173q0 .344-.233.576t-.575.232h-3.462q-.343 0-.575-.232t-.233-.576M12 5.25l-5.486 5.867q-.074.07-.173.111t-.196.041q-.32 0-.457-.296q-.138-.296.095-.546l5.62-6.02q.238-.253.595-.253t.598.254l5.621 6.019q.214.25.096.546q-.119.296-.46.296q-.105 0-.2-.035t-.166-.117z");
}

</style>
