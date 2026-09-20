<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6efltbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:kid-star-outline" /></template>
<style>
.b6efltbgb {
  fill: currentColor;
  d: path("m8.125 7.092l2.608-3.47q.242-.324.568-.473T12 3t.699.149t.568.472l2.608 3.471l4.02 1.368q.534.18.822.602t.289.938q0 .242-.069.475t-.23.45l-2.634 3.573l.1 3.83q.025.703-.47 1.188q-.493.484-1.14.484l-.453-.056L12 18.733l-4.11 1.211q-.124.05-.236.053T7.437 20q-.666 0-1.15-.484q-.485-.485-.46-1.187l.1-3.856l-2.629-3.548q-.161-.217-.23-.45T3 10q0-.51.295-.941t.83-.618zm.629.86L4.462 9.398q-.289.096-.395.394t.087.548l2.792 3.84l-.119 4.16q-.02.327.23.52q.25.192.559.096L12 17.696l4.385 1.285q.307.096.557-.096q.25-.193.231-.52l-.12-4.184l2.793-3.79q.192-.25.087-.549q-.106-.298-.395-.394l-4.292-1.496l-2.765-3.683q-.173-.25-.481-.25t-.48.25zM12 11.519");
}

</style>
